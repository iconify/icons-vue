<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl11knbwz.css';
import '../../css/m/m2ikeob3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl11knbwz"/><path class="m2ikeob3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:programming-user-code" /></template>
