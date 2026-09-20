<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae8_uoo2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae8_uoo2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tree-pine" /></template>
