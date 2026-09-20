<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uagxnh7qx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uagxnh7qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:umbrella-outline" /></template>
