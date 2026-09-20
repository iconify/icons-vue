<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4xu1qpuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nutrition-outline" /></template>
<style>
.n4xu1qpuv {
  fill: currentColor;
  d: path("M7.749 18.251Q6 16.502 6 14q0-2.061 1.243-3.674t3.243-2.128q-.5-.106-.984-.324q-.485-.218-.84-.574q-.672-.671-.87-1.587q-.2-.917-.17-1.861q.905-.029 1.792.16t1.559.823q.575.517.818 1.232q.243.716.3 1.497q.305-.737.739-1.396q.433-.658 1.008-1.233q.14-.14.354-.14t.354.14t.14.354t-.14.353q-.53.531-.937 1.145q-.405.615-.663 1.307q2.2.335 3.627 2.009T18 14q0 2.502-1.749 4.251T12 20t-4.251-1.749m7.789-.713Q17 16.075 17 14t-1.463-3.537T12 9t-3.537 1.463T7 14t1.463 3.538T12 19t3.538-1.463M12 14");
}

</style>
