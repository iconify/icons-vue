<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k71nsubdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k71nsubdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-right-up-bold" /></template>
