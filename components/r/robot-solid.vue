<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnr-gfdrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnr-gfdrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:robot-solid" /></template>
