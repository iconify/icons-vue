<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znq7qdb9f.css';
import '../../css/a/ak0d4abdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary znq7qdb9f"/><path class="ak0d4abdn primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:spade-duo" /></template>
