<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iky3mbb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iky3mbb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:moon-foggy-line" /></template>
