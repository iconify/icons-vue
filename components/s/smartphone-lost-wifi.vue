<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irougxzdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irougxzdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:smartphone-lost-wifi" /></template>
