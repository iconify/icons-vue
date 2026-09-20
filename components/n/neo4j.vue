<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtj_33k3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtj_33k3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:neo4j" /></template>
