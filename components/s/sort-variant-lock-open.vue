<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v26jpc9-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v26jpc9-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-variant-lock-open" /></template>
