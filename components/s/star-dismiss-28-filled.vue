<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="b3zvkdb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-dismiss-28-filled" /></template>
<style>
.b3zvkdb-n {
  fill: currentColor;
  d: path("M12.701 3.908c.532-1.078 2.069-1.078 2.6 0l2.692 5.452l6.017.875c1.19.173 1.664 1.634.804 2.473l-1.06 1.033a7.5 7.5 0 0 0-10.587 8.342l-4.547 2.39c-1.064.56-2.307-.343-2.104-1.528l1.028-5.993l-4.355-4.244c-.86-.839-.385-2.3.804-2.473l6.017-.875zM27 20.5a6.5 6.5 0 1 1-13 0a6.5 6.5 0 0 1 13 0m-9.146-3.354a.5.5 0 0 0-.708.707l2.647 2.646l-2.647 2.647a.5.5 0 0 0 .708.707l2.646-2.646l2.646 2.646a.5.5 0 0 0 .708-.707L21.207 20.5l2.647-2.647a.5.5 0 0 0-.708-.707L20.5 19.792z");
}

</style>
