<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt8wyto3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kt8wyto3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-double-alt-arrow-up-outline" /></template>
