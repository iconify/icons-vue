<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2s83vb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2s83vb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:speaker-off" /></template>
