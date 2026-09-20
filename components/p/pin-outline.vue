<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4205ac_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k4205ac_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pin-outline" /></template>
