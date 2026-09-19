<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmsdlybyh.css';
import '../../css/u/ulimznb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tmsdlybyh"/><path class="ulimznb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:present-solid" /></template>
