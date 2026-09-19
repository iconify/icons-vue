<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6d9bfo-j.css';
import '../../css/e/ezjzxdbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6d9bfo-j"/><path class="ezjzxdbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:spreadsheet" /></template>
