<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9tf64bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="m9tf64bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:search-circle-solid" /></template>
