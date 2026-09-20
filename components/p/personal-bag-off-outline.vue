<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh239jmcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:personal-bag-off-outline" /></template>
<style>
.nh239jmcc {
  fill: currentColor;
  d: path("M12 3.846q.91 0 1.532.64q.622.639.622 1.549v.396q1.66.652 2.753 2.115T18 12v3.573l-1-1V12q0-2.075-1.463-3.537T12 7q-.673 0-1.178.139q-.505.138-.891.326l-.085-.084V6q0-.904.625-1.529T12 3.846m-.818 1.336q-.336.335-.336.818v.138q.295-.069.577-.104Q11.706 6 12 6t.577.034t.577.105V6q0-.483-.336-.818T12 4.846t-.818.336m9.31 17.11L11.69 13.5H8.5v-1h2.189L7.696 9.508q-.361.54-.529 1.199T7 12v7.385q0 .23.192.423t.423.192h8.77q.23 0 .423-.192t.192-.424v-2l1 1v1q0 .691-.462 1.153T16.384 21H7.616q-.691 0-1.153-.462T6 19.385V12q0-.9.241-1.718q.242-.819.725-1.505L2.86 4.662l.708-.708L21.2 21.584zM12 14.754");
}

</style>
