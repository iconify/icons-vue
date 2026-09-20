<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnixv7h1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnixv7h1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:signal-cellular-2-line" /></template>
