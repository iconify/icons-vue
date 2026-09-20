<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu8cyhbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tu8cyhbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-cog" /></template>
