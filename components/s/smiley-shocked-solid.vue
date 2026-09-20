<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdks22bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jdks22bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:smiley-shocked-solid" /></template>
