<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zawcccb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zawcccb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mask-filled" /></template>
