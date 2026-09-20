<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch9gw4nfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-input-svideo" /></template>
<style>
.ch9gw4nfk {
  fill: currentColor;
  d: path("M8.503 20.293q-1.64-.708-2.864-1.932t-1.931-2.864T3 11.995t.71-3.5T5.64 5.64t2.862-1.93Q10.147 3 12.005 3t3.498.71t2.858 1.93t1.929 2.855q.71 1.637.71 3.5t-.71 3.505t-1.93 2.86t-2.855 1.93t-3.5.71t-3.502-.707m-.267-8.057q.302-.303.302-.736t-.302-.735q-.303-.304-.736-.304t-.735.303t-.303.736t.303.736q.302.302.735.302t.736-.302m9 0q.303-.303.303-.736t-.303-.735t-.736-.304t-.735.303q-.304.303-.304.736t.303.736q.303.302.736.302t.736-.302m-7.5 4.5q.303-.303.303-.736t-.303-.735Q9.433 14.96 9 14.96t-.735.303t-.303.736t.303.736t.735.303t.736-.303m6 0q.303-.303.303-.736t-.303-.735q-.303-.304-.736-.304t-.735.303t-.303.736t.303.736q.302.303.735.303t.736-.303M10.5 8.539h3q.439 0 .739-.3t.3-.739t-.3-.738t-.739-.3h-3q-.438 0-.738.3t-.3.738t.3.739t.738.3");
}

</style>
