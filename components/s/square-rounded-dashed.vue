<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thrkkh5dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="thrkkh5dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:square-rounded-dashed" /></template>
