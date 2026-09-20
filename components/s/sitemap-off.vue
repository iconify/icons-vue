<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr5g377_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr5g377_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sitemap-off" /></template>
