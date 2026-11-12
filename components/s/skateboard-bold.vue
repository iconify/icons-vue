<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vskr90bqk"/><path class="kdjsh1b9r"/><path class="jlmj2df4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skateboard-bold" /></template>
<style>
.jlmj2df4o {
  fill: currentColor;
  d: path("M19.0001 15C19.0001 16.1045 18.1046 17 17.0001 17C15.8955 17 15.0001 16.1045 15.0001 15C15.0001 13.8954 15.8955 13 17.0001 13C18.1046 13 19.0001 13.8954 19.0001 15Z");
}

.kdjsh1b9r {
  fill: currentColor;
  d: path("M9.00008 15C9.00008 16.1045 8.10465 17 7.00008 17C5.89551 17 5.00008 16.1045 5.00008 15C5.00008 13.8954 5.89551 13 7.00008 13C8.10465 13 9.00008 13.8954 9.00008 15Z");
}

.vskr90bqk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.58405 6.37592C1.9287 6.14616 2.39435 6.23929 2.62412 6.58393L3.43665 7.80273C4.03942 8.70688 5.05417 9.24996 6.14081 9.24996H17.8593C18.946 9.24996 19.9607 8.70688 20.5635 7.80273L21.376 6.58393C21.6058 6.23929 22.0715 6.14616 22.4161 6.37592C22.7608 6.60568 22.8539 7.07134 22.6241 7.41598L21.8116 8.63478C20.9306 9.95623 19.4475 10.75 17.8593 10.75H6.14081C4.55264 10.75 3.06954 9.95623 2.18858 8.63478L1.37604 7.41598C1.14628 7.07134 1.23941 6.60568 1.58405 6.37592Z");
}

</style>
