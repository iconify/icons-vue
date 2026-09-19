<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq7m4_bez.css';
import '../../css/m/mxlpzmyqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jq7m4_bez"/><path class="mxlpzmyqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:virtual-reality-outlined" /></template>
