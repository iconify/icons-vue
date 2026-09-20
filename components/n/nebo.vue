<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfcqqsmiv.css';
import '../../css/r/ryf4c_b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfcqqsmiv"/><path class="ryf4c_b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nebo" /></template>
