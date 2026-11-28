<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl4o75bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl4o75bnp primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pentagon-duotone" /></template>
