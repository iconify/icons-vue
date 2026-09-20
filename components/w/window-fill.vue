<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjh33ebuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vjh33ebuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:window-fill" /></template>
