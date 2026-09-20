<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ronm36v_x.css';
import '../../css/e/erf0i1n1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ronm36v_x"/><path class="erf0i1n1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tongue-line" /></template>
