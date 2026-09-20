<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pksp8bbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pksp8bbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:podium-third" /></template>
