<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duozttb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duozttb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:water-glass-fill" /></template>
