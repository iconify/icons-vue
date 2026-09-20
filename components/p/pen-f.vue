<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tly_ixbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-3};
const content = `<path class="tly_ixbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:pen-f" /></template>
