<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nucobebyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nucobebyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:resize" /></template>
