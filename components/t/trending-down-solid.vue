<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eobfair3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eobfair3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:trending-down-solid" /></template>
