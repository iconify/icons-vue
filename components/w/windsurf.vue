<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw12u9--k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw12u9--k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:windsurf" /></template>
