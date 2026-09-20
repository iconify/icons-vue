<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqqo41bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqqo41bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:viewport-wide" /></template>
