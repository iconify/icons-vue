<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvu1cpbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvu1cpbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pyramid" /></template>
