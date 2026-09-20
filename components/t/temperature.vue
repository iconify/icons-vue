<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndjatbbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndjatbbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:temperature" /></template>
