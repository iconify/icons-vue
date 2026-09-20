<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv-lqzb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv-lqzb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:master-card" /></template>
