<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfw4d2b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sfw4d2b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:safari-solid" /></template>
