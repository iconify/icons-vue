<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="sprolej3b"/><path class="z429yabqt"/><path class="ohppmmbbi"/><path class="eczczrbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:peach" /></template>
<style>
.eczczrbvz {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M22.999 30a1 1 0 0 1-.831-1.555C22.183 28.423 24 25.538 24 19c0-6.445-4.578-10.182-4.625-10.219a1 1 0 1 1 1.25-1.561C20.844 7.395 26 11.604 26 19c0 7.22-2.079 10.422-2.168 10.555a1 1 0 0 1-.833.445");
}

.ohppmmbbi {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M1.062 5.125s4.875-5 10-5C17.188.125 19 5.062 19 5.062s-4.062 5.25-8.062 4.25s-9.876-4.187-9.876-4.187");
}

.sprolej3b {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M1.062 5.125s4.875-5 10-5C17.188.125 19 5.062 19 5.062s.625-4 5-4s6.938 3.125 6.938 3.125s-3.562 2.125-4.625 2.562c-2.801 1.153-11.375 3.562-15.375 2.562S1.062 5.125 1.062 5.125");
}

.z429yabqt {
  fill: var(--svg-color--ff886c, #ff886c);
  d: path("M18 6s1.042-.896 6-.896c6.542 0 12 4.812 12 12.927c0 11.531-14.958 17.881-14.958 17.881S1 34.833 1 17.977C1 8.018 7.75 5 12 5c4.958 0 6 1 6 1");
}

</style>
