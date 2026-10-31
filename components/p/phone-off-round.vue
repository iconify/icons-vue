<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ualn45blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ualn45blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-off-round" /></template>
