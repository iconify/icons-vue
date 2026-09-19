<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcvre0bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcvre0bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:search-alt-2" /></template>
