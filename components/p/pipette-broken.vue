<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/murvr1lpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="murvr1lpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pipette-broken" /></template>
