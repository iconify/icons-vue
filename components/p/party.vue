<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cprdexzeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cprdexzeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:party" /></template>
