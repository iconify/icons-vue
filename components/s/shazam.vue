<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niv8vb25t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="niv8vb25t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:shazam" /></template>
