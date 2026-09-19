<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh2817vyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh2817vyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:washington-monument" /></template>
