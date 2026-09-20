<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5zgvz3hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sticker-outline-sharp" /></template>
<style>
.z5zgvz3hb {
  fill: currentColor;
  d: path("M11.5 14.73q1.494 0 2.654-.922q1.16-.923 1.5-2.373L8.5 13.454q.592.627 1.367.952t1.633.325m-4.073-3.712l2.38-.673q.062-.565-.33-.985q-.392-.419-.977-.419q-.548 0-.928.38t-.38.928q0 .217.071.4t.164.37m6-1.75l2.38-.674q.068-.565-.327-.985t-.98-.419q-.548 0-.928.38t-.38.928q0 .217.071.4t.164.37M15.577 20H4V4h16v11.577zM15 19v-4h4V5H5v14zM5 19V5z");
}

</style>
