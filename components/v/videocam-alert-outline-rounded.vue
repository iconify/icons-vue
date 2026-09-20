<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtlhb3a6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:videocam-alert-outline-rounded" /></template>
<style>
.mtlhb3a6k {
  fill: currentColor;
  d: path("M12.689 19q-.214 0-.357-.143t-.143-.357t.143-.357t.357-.143h3.177q.269 0 .442-.173t.173-.442V6.615q0-.269-.173-.442T15.866 6H5.096q-.269 0-.442.173t-.173.443v2.717q0 .213-.144.357t-.356.143t-.357-.143t-.143-.357V6.616q0-.691.462-1.153T5.096 5h10.77q.69 0 1.152.463t.463 1.153v4.653l2.342-2.342q.193-.192.444-.096q.252.096.252.369v5.6q0 .273-.252.37q-.251.095-.444-.097l-2.342-2.342v4.654q0 .69-.463 1.153T15.866 19zm-9.524-.164Q2 17.67 2 16t1.165-2.835T6 12t2.836 1.165T10 16t-1.164 2.836T6 20t-2.835-1.164M6 18.423q.2 0 .33-.13t.132-.332t-.131-.33T6 17.5t-.33.13t-.132.332t.131.33t.331.131m0-1.846q.162 0 .273-.112q.112-.111.112-.273v-2.23q0-.162-.112-.274T6 13.577t-.273.112t-.111.273v2.23q0 .162.111.274q.112.111.273.111M10.48 12");
}

</style>
