<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sosnmzn2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sosnmzn2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-68-small" /></template>
