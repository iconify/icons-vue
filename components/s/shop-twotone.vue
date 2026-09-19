<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2h-50wuc.css';
import '../../css/i/imgt2lbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d2h-50wuc"/><path class="imgt2lbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:shop-twotone" /></template>
