<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvvf-pbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yvvf-pbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:meditation-round-outline" /></template>
