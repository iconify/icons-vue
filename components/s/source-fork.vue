<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe-cvhtta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe-cvhtta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:source-fork" /></template>
