<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elbjalsew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="elbjalsew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:rest-filled" /></template>
