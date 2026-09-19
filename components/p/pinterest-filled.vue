<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4azuyx3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s4azuyx3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:pinterest-filled" /></template>
