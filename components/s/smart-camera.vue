<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqi269k2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqi269k2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:smart-camera" /></template>
