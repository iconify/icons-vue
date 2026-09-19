<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhg4nbcno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhg4nbcno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:medium" /></template>
