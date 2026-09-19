<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwna3ebpo.css';
import '../../css/v/vfiksfbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cwna3ebpo"/><path class="vfiksfbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:translation" /></template>
