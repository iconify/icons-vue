<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q53v49bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q53v49bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-plus" /></template>
