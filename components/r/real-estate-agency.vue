<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehev4sv_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ehev4sv_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:real-estate-agency" /></template>
