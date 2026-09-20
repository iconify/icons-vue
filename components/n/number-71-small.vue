<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-58qssej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-58qssej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-71-small" /></template>
