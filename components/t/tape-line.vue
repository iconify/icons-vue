<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr5fm0bhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr5fm0bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:tape-line" /></template>
