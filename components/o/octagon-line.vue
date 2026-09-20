<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5qmm2sbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5qmm2sbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:octagon-line" /></template>
