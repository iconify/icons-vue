<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv84hl_xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:unarchive-rounded" /></template>
<style>
.bv84hl_xl {
  fill: currentColor;
  d: path("M12.357 16.801q.143-.143.143-.357v-4.2l1.746 1.746q.14.14.344.15t.364-.15t.16-.354t-.16-.353L12.565 10.9q-.242-.242-.565-.242t-.566.242l-2.388 2.383q-.14.14-.15.344t.15.364t.354.159t.354-.16l1.746-1.746v4.2q0 .214.143.357t.357.143t.357-.143M5.769 20q-.671 0-1.22-.549T4 18.231V7.486q0-.292.093-.55t.28-.475l1.558-1.87q.217-.293.543-.442T7.173 4h9.616q.372 0 .708.149t.553.441l1.577 1.91q.187.217.28.485q.093.267.093.56V18.23q0 .671-.549 1.22t-1.22.549zM5.381 6.808H18.6L17.27 5.21q-.097-.096-.222-.153T16.788 5H7.192q-.134 0-.26.058t-.22.154z");
}

</style>
