<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtvf1bb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtvf1bb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-grid-small-fill-round" /></template>
