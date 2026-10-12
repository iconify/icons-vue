<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh-hjpb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh-hjpb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:squares-unite-filled" /></template>
