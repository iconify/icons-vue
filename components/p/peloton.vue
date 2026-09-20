<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezcex-blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezcex-blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:peloton" /></template>
