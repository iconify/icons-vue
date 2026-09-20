<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d784c_dkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d784c_dkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sync" /></template>
