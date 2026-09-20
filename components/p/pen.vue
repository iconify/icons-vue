<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvy4vpqps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvy4vpqps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:pen" /></template>
