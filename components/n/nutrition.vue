<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn-i8lbtr.css';
import '../../css/r/r5r-9rbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zn-i8lbtr"/><path class="r5r-9rbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:nutrition" /></template>
