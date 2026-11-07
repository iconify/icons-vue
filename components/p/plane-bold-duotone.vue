<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua6aqkoxj.css';
import '../../css/d/d4zi-lbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ua6aqkoxj"/><path class="d4zi-lbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plane-bold-duotone" /></template>
