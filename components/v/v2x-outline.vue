<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu8bbgk9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pu8bbgk9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:v2x-outline" /></template>
