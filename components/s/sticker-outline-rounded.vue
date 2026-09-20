<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z781i0jap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sticker-outline-rounded" /></template>
<style>
.z781i0jap {
  fill: currentColor;
  d: path("M11.5 14.73q1.408 0 2.51-.814q1.104-.814 1.53-2.108q.05-.131-.046-.224t-.227-.044L8.93 13.323q-.142.05-.18.19t.088.245q.548.465 1.232.719q.685.254 1.431.254m-4.073-3.712l2.38-.673q.062-.565-.33-.985q-.392-.419-.977-.419q-.548 0-.928.38t-.38.928q0 .217.071.4t.164.37m6-1.75l2.38-.674q.068-.565-.327-.985t-.98-.419q-.548 0-.928.38t-.38.928q0 .217.071.4t.164.37M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v9.29q0 .323-.13.628q-.132.305-.349.522l-3.465 3.465q-.218.218-.522.348q-.305.131-.628.131zM15 19v-2q0-.825.588-1.412T17 15h2V5.616q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192zM5 19V5z");
}

</style>
