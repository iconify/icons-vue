<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3_kvuzgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3_kvuzgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-2" /></template>
