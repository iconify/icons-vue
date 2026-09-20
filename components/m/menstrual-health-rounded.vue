<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfmzjyjhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:menstrual-health-rounded" /></template>
<style>
.nfmzjyjhn {
  fill: currentColor;
  d: path("M5.21 17.563q-.187 0-.312-.136q-.923-1.16-1.41-2.548Q3 13.49 3 12V6.115q0-.51.444-.726t.848.08L7.508 7.89q.217.162.264.417t-.09.472q-.847 1.454-1.515 2.993Q5.5 13.312 5.5 15q0 .43.067.849t.189.83q.082.275-.001.465q-.084.19-.22.304q-.137.114-.325.115m2.896 1.331Q6.5 17.29 6.5 15q0-1.664 1.171-4.183t3.335-5.348q.379-.484.994-.494t.994.494q2.158 2.823 3.332 5.346Q17.5 13.337 17.5 15q0 2.289-1.606 3.894T12 20.5t-3.894-1.606m10.08-1.722q-.074-.213.058-.493q.122-.412.189-.83T18.5 15q0-1.689-.677-3.228t-1.506-2.993q-.136-.217-.089-.472t.264-.417l3.216-2.42q.404-.299.848-.081t.444.726V12q0 1.49-.488 2.879q-.487 1.388-1.41 2.548q-.12.162-.32.173t-.36-.102t-.237-.326");
}

</style>
