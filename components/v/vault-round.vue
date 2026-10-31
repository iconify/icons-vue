<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w27teki7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w27teki7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vault-round" /></template>
