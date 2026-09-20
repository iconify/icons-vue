<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk3da0fkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk3da0fkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sun-line" /></template>
