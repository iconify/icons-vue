<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywlt9kj8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywlt9kj8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:passport-check" /></template>
