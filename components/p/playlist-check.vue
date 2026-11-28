<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk6kzsnsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk6kzsnsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:playlist-check" /></template>
