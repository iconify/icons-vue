<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flf817bsl.css';
import '../../css/u/ufhkon_xc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="flf817bsl"/><path class="ufhkon_xc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:star-twotone" /></template>
