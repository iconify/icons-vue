<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azacp831x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="azacp831x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-double-alt-arrow-up-bold" /></template>
