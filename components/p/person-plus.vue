<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-32uzi1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-32uzi1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:person-plus" /></template>
