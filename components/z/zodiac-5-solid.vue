<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwtctub0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mwtctub0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:zodiac-5-solid" /></template>
