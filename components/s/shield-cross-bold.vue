<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxy7-ob-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oxy7-ob-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-cross-bold" /></template>
