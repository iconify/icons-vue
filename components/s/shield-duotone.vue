<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg8kaubnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg8kaubnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-duotone" /></template>
