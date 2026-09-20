<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mehx9bbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mehx9bbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:transportforireland" /></template>
