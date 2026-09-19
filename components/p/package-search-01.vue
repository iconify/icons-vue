<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v76gq-blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v76gq-blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:package-search-01" /></template>
