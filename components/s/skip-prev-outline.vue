<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu_3bybmc.css';
import '../../css/k/ki8ztfb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu_3bybmc"/><path clip-rule="evenodd" class="ki8ztfb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:skip-prev-outline" /></template>
