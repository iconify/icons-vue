<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhoum_bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhoum_bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rolodex" /></template>
