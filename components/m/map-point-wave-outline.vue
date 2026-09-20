<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o59xxcb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o59xxcb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-wave-outline" /></template>
