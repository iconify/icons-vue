<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="rwjyxgbzi"/><path clip-rule="evenodd" class="wdoivwk-q"/><path class="c1fd7ebzf"/><path clip-rule="evenodd" class="tau1ufbwb"/><path clip-rule="evenodd" class="euy1e0bii"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:next-track-circle" /></template>
<style>
.c1fd7ebzf {
  d: path("M17.863 12.318a1 1 0 0 1 0 1.364l-4.632 4.963c-.62.664-1.731.226-1.731-.682V8.037c0-.908 1.112-1.346 1.731-.682z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.euy1e0bii {
  fill-rule: evenodd;
  d: path("M18.5 7a1 1 0 0 1 1 1v10a1 1 0 1 1-2 0V8a1 1 0 0 1 1-1");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.rwjyxgbzi {
  d: path("M12.863 12.318a1 1 0 0 1 0 1.364l-4.632 4.963c-.62.664-1.731.226-1.731-.682V8.037c0-.908 1.112-1.346 1.731-.682z");
}

.tau1ufbwb {
  fill-rule: evenodd;
  d: path("M15.764 13L13.5 10.574v4.852zm2.1.682a1 1 0 0 0 0-1.364L13.23 7.355c-.62-.664-1.731-.226-1.731.682v9.926c0 .908 1.112 1.346 1.731.682z");
}

.wdoivwk-q {
  fill-rule: evenodd;
  d: path("M10.764 13L8.5 10.574v4.852zm2.1.682a1 1 0 0 0 0-1.364L8.23 7.355c-.62-.664-1.731-.226-1.731.682v9.926c0 .908 1.112 1.346 1.731.682z");
}

</style>
