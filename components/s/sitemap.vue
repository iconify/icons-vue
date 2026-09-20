<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_wzp1b0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_wzp1b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sitemap" /></template>
