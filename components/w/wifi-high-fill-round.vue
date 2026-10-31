<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-db-jbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-db-jbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wifi-high-fill-round" /></template>
