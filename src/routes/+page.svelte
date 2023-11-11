<script>
  /** import {MyImage} from "../assets/im3rd-media-wDJ80Pl66mg-unsplash-2000.jpg"
   * throws a 500 error
   */

  /* this works */
  import MyImage from '../assets/im3rd-media-wDJ80Pl66mg-unsplash-2000.jpg?enhanced';
</script>

<h1>Debug: `enhanced-img` import</h1>

<enhanced:img src={MyImage} alt="" />

<style>
  :global(img) {
    max-width: 100%;
    height: auto;
  }
</style>
