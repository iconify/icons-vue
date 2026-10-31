<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj17cl5vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj17cl5vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vault-fill-round" /></template>
