<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khaod37pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="khaod37pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:soundwave-circle-outline" /></template>
