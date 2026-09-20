<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0-dt9s6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0-dt9s6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:selection-multiple-location" /></template>
