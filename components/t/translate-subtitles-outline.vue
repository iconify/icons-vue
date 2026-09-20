<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugmhhh4yq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:translate-subtitles-outline" /></template>
<style>
.ugmhhh4yq {
  fill: currentColor;
  d: path("m3.73 18.308l-.613-.647l2.94-2.852q-.545-.665-1.019-1.361T4.16 12h.981q.331.579.698 1.117t.816 1.056q.742-.842 1.342-1.765t.956-1.985H2v-.885h4.23V8.231h.885v1.307h4.624v.885H9.858q-.406 1.235-1.084 2.315q-.678 1.081-1.537 2.066q.369.425.812.862t.851.807l-.344.89q-.464-.419-.971-.914q-.508-.495-.95-.988zm4.299 4.23l3.433-8.769h.932l3.452 8.77h-.954l-.92-2.416H9.903l-.935 2.415zm2.177-3.196h3.463l-1.735-4.511zM12.98 9.54h3.308v-.885H12.98zm4.923 0h.885v-.885h-.885zm-7.558-2.75h.885v-.885h-.885zm2.308 0h6.135v-.885h-6.135zm.327 5.98v-.885h7.692q.173 0 .308-.115q.134-.115.134-.269V3.27q0-.155-.134-.27q-.135-.116-.308-.116H8.462q-.174 0-.308.116q-.135.116-.135.27v3.71h-.885V3.27q0-.53.377-.9t.95-.37h12.212q.573 0 .95.37t.377.9v8.23q0 .529-.377.899t-.95.37zm8.135-.885v-9z");
}

</style>
