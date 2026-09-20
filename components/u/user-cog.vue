<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upc0qvbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upc0qvbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:user-cog" /></template>
