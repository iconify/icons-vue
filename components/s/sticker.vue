<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo3p3rbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sticker" /></template>
<style>
.fo3p3rbku {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v9.961L15.577 20zm7.811-10.73l2.38-.674q.068-.565-.327-.985t-.98-.419q-.548 0-.928.38t-.38.928q0 .217.071.4t.164.37m-6 1.75l2.38-.674q.062-.565-.33-.985q-.392-.419-.977-.419q-.548 0-.928.38t-.38.928q0 .217.071.4t.164.37m4.073 3.71q1.494 0 2.654-.922q1.16-.923 1.5-2.373L8.5 13.454q.592.627 1.367.952t1.633.325M15 19l4-4h-2q-.825 0-1.412.588T15 17z");
}

</style>
