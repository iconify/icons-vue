<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoa89xbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="xoa89xbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:minus-sign" /></template>
