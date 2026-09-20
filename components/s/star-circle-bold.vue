<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apl9sq3xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="apl9sq3xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-circle-bold" /></template>
