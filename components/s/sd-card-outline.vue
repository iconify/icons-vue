<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-mrvim6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g-mrvim6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sd-card-outline" /></template>
