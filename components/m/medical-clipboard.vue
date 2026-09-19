<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-oso6bmy.css';
import '../../css/n/nhbth2b0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-oso6bmy"/><path class="nhbth2b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:medical-clipboard" /></template>
