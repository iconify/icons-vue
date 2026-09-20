<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5f1s0biu.css';
import '../../css/z/zput1obaq.css';
import '../../css/c/c6q4vpbxk.css';
import '../../css/d/da06ybbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i5f1s0biu"/><path class="zput1obaq"/><path clip-rule="evenodd" class="c6q4vpbxk"/><path clip-rule="evenodd" class="da06ybbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:page-setup-16" /></template>
