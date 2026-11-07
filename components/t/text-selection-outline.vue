<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6bxffbta.css';
import '../../css/l/lh-_3in4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6bxffbta"/><path clip-rule="evenodd" class="lh-_3in4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-selection-outline" /></template>
