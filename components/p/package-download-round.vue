<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulw2hdb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulw2hdb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-download-round" /></template>
