<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px_ujgm9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px_ujgm9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:user-outline" /></template>
