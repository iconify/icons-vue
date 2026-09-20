<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m98sc-b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m98sc-b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-off" /></template>
