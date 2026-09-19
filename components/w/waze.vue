<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt560hjnz.css';
import '../../css/b/bk7elybvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt560hjnz"/><path class="bk7elybvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:waze" /></template>
