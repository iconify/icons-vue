<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc3fdx9jx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc3fdx9jx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:repeat-off" /></template>
