<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r74e7hbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r74e7hbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:navigation-line" /></template>
