<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp-6atb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gp-6atb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:search-virus" /></template>
