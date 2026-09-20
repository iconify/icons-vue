<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg7d74d9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg7d74d9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-arrow-up-bold" /></template>
