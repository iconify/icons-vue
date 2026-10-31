<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn9smw17t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn9smw17t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:search-fill-round" /></template>
