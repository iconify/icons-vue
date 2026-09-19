<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruq9-4b_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruq9-4b_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:villa-01" /></template>
