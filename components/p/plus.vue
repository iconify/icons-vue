<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt85k4fna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt85k4fna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:plus" /></template>
