<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miuz52b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="miuz52b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-ribbons-star-outline" /></template>
