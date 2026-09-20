<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnawj1_sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wnawj1_sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-boarding-steam-train-on-railway-track" /></template>
