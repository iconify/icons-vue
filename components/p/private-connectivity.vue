<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fero-5bec.css';
import '../../css/c/ci3wxgbkl.css';
import '../../css/i/i-v3-zb2d.css';
import '../../css/m/miprkwbjz.css';
import '../../css/s/s6xzyh3xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fero-5bec"/><circle class="ci3wxgbkl"/><path class="i-v3-zb2d"/><path class="miprkwbjz"/><circle class="s6xzyh3xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:private-connectivity" /></template>
