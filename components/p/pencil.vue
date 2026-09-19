<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icwu4ka3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icwu4ka3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:pencil" /></template>
