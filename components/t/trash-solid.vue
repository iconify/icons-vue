<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-2odwape.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-2odwape"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:trash-solid" /></template>
