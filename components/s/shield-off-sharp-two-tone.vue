<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s3k2df2wo"/><path class="rxa0t3b0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rxa0t3b0q {
  d: path("M18.1442 18.1442C16.9368 19.5385 15.1796 20.9892 12.8298 21.8525C12.2945 22.0492 11.7055 22.0492 11.1702 21.8525C8.4967 20.8703 6.5903 19.1277 5.388 17.5729L4 15.7778L4 5.3088L5.1699 5.1699M1.7071 1.7071L22.2929 22.2929");
}

.s3k2df2wo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.8518 18.8518C17.567 20.3105 15.6493 21.882 13.1746 22.7912C12.4724 23.0492 11.5276 23.0492 10.8253 22.7911C7.9672 21.7411 5.852 19.8076 4.5969 18.1846L3.2089 16.3895C3.0735 16.2143 3 15.9992 3 15.7778L3 5.3088C3 4.8021 3.379 4.3755 3.8821 4.3158L4.2698 4.2698L18.8518 18.8518ZM7.2825 3.6256C8.576 3.1223 9.5822 2.3789 10.3279 1.6554C11.1316 0.8756 12.8684 0.8756 13.6721 1.6554C14.7999 2.7495 16.5233 3.8892 18.9353 4.1754L20.1179 4.3158C20.621 4.3755 21 4.8021 21 5.3088L21 15.778C21 15.9994 20.9265 16.2146 20.7911 16.3897L20.4664 16.8096L7.2825 3.6256Z");
  stroke: none;
}

</style>
