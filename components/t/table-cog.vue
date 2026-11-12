<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrcztlefp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrcztlefp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:table-cog" /></template>
