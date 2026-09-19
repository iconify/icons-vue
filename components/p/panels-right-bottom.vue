<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-gr4qbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-gr4qbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:panels-right-bottom" /></template>
