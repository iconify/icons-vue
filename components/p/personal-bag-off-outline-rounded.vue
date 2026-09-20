<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf2ckkb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:personal-bag-off-outline-rounded" /></template>
<style>
.cf2ckkb9k {
  fill: currentColor;
  d: path("M12 3.846q.916 0 1.535.64q.619.639.619 1.549v.396q1.66.652 2.753 2.115T18 12v2.616q0 .25-.159.375q-.158.125-.341.125t-.341-.128T17 14.61V12q0-2.075-1.463-3.537T12 7h-1.346q-.402 0-.701-.299q-.3-.299-.3-.701q.155-.904.799-1.529T12 3.846m-.818 1.336q-.336.335-.336.818v.138q.295-.069.577-.104Q11.706 6 12 6t.577.034t.577.105V6q0-.483-.336-.818T12 4.846t-.818.336m8.957 16.757l-8.45-8.439H9q-.213 0-.357-.143T8.5 13t.143-.357T9 12.5h1.689L7.696 9.508q-.361.54-.529 1.199T7 12v7.385q0 .23.192.423t.423.192h8.77q.23 0 .423-.192t.192-.424v-2l1 1v1q0 .691-.462 1.153T16.384 21H7.616q-.691 0-1.153-.462T6 19.385V12q0-.9.241-1.718q.242-.819.725-1.505l-3.75-3.762q-.141-.14-.154-.341t.154-.366q.159-.16.353-.16t.354.16L20.846 21.23q.14.14.153.341t-.153.367q-.16.159-.354.159t-.354-.16M12 14.754");
}

</style>
