<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzbaq923d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dzbaq923d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:shopping-outline" /></template>
