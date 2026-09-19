<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9xelbb4d.css';
import '../../css/y/yv_brepse.css';
import '../../css/l/lpz0abbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k9xelbb4d"/><path class="yv_brepse"/><path class="lpz0abbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:right-circle-twotone" /></template>
