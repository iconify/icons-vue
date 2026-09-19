<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e89cb6bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="e89cb6bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:wechat-filled" /></template>
