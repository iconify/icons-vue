<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypqbqhb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sticker-add-outline" /></template>
<style>
.ypqbqhb5p {
  fill: currentColor;
  d: path("M11.5 14.73q1.494 0 2.654-.922q1.16-.923 1.5-2.373L8.5 13.454q.592.627 1.367.952t1.633.325m-4.073-3.712l2.38-.673q.062-.565-.325-.985t-.991-.419q-.539 0-.919.382q-.38.381-.38.926q0 .217.072.4q.07.183.163.37m6-1.75l2.38-.674q.068-.565-.323-.985q-.392-.419-.984-.419q-.545 0-.926.382t-.382.926q0 .217.072.4q.07.183.163.37M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h9v1h-9q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192H15v-2q0-.825.588-1.412T17 15h2V9.385h1v6.192L15.577 20zM19 7V5h-2V4h2V2h1v2h2v1h-2v2z");
}

</style>
