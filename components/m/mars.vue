<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk64cac5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk64cac5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mars" /></template>
