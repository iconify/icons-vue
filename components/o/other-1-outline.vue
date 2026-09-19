<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykq3zccqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykq3zccqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:other-1-outline" /></template>
