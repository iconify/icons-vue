<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-1l6vtvu.css';
import '../../css/z/zdawap23x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-1l6vtvu"/><path class="zdawap23x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pill-bold-duotone" /></template>
