<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbgo6bc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:replace-audio-outline-rounded" /></template>
<style>
.zbgo6bc9i {
  fill: currentColor;
  d: path("M19.192 8.77h-3.461q-.214 0-.357-.144t-.143-.357t.143-.357t.357-.143h2.361q-.84-1.725-2.49-2.747T12 4Q9.86 4 8.108 5.174t-2.53 3.124q-.119.25-.307.306t-.365-.023t-.267-.275t-.005-.367q.893-2.237 2.898-3.588T12 3q2.223 0 4.099 1.144T19 7.234V4.5q0-.213.143-.357T19.5 4t.357.143T20 4.5v3.462q0 .348-.23.578t-.578.23M8.832 20.205q-.793-.794-.793-1.937t.794-1.936t1.936-.794q.497 0 .939.18t.792.49v-5.055h4v1h-3v6.115q0 1.143-.794 1.937T10.769 21t-1.936-.794");
}

</style>
