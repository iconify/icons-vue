<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="ehy-egfbp"><path class="fvtafhbxd"/><path class="gzgj63bhy"/></g><path class="q8smlc00m"/><path class="v3lw73grl"/><path class="b1tzxkbix"/><path class="gt0u7bbbk"/><g class="a544ggv4z"><path class="qayiwkb6s"/><path class="af7hlja8t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:toilet" /></template>
<style>
.a544ggv4z {
  fill: var(--svg-color--a7a8ac, #a7a8ac);
}

.af7hlja8t {
  d: path("m33.12 30.521l4.412-25.683s2.458-.597 3.752 1.388l-4.198 24.431z");
}

.b1tzxkbix {
  fill: var(--svg-color--e7e6e6, #e7e6e6);
  d: path("M39.581 34.74c-15.354 2.908-28.905.717-30.423.3c-.199-.021-1.762-.889-1.959-.922c-.002.007-.094.75-.096.761c-12.415 20.1 16.44 19.335 16.44 19.335c23.753-1.208 16.04-19.474 16.04-19.474");
}

.ehy-egfbp {
  fill: var(--svg-color--e7e6e6, #e7e6e6);
}

.fvtafhbxd {
  d: path("M60.881 25.19c0 6.779-5.527 12.278-12.343 12.278S36.197 31.969 36.197 25.19V12.278C36.197 5.5 41.722.001 48.538.001S60.881 5.5 60.881 12.278z");
}

.gt0u7bbbk {
  fill: var(--svg-color--808284, #808284);
  d: path("M47.909 32.634H5.224S3.58 33.879 6.436 34.74h40.607z");
}

.gzgj63bhy {
  d: path("M54.671 35.846s-5.824 2.455-6.133 12.609c0 0-2.421-1.601-2.321-2.301c.1-.702-.756-8.688-.756-8.688l4.073-2.727zM7.989 33.17s2.998-2.541 4.7-3.063h29.568l.889 3.575H25.57z");
}

.q8smlc00m {
  fill: var(--svg-color--a7a8ac, #a7a8ac);
  d: path("M20.309 49.657s-6.874 8.521-6.556 13.885h34.786V32.634H34.661l-14.352 17.02");
}

.qayiwkb6s {
  d: path("M57.691 1.944h-17.06s-.658 1.248.481 2.109h16.231l.345-2.109M34.731 27.15H11.27s-.899 2.07.668 3.505h22.316z");
}

.v3lw73grl {
  fill: var(--svg-color--aeacac, #aeacac);
  d: path("m7.321 35.461l.853-2.827h30.575s.907 2.933 1.407 3.879c.577 1.091.54 1.875-.06 1.138c0 0-3.621 4.885-3.906 4.885c-.284 0-23.969 1.426-24.18 1.632c-.211.208-4.691-8.707-4.691-8.707");
}

</style>
