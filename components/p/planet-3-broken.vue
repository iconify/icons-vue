<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2togz17h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2togz17h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:planet-3-broken" /></template>
