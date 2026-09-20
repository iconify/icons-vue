<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4rta8squ.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4rta8squ"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:moonset" /></template>
