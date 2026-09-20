<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpwtkbckd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpwtkbckd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ukca" /></template>
