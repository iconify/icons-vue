<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdmiocz9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sdmiocz9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-double-alt-arrow-left-outline" /></template>
