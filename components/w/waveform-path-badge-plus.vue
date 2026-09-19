<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2e61izjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="n2e61izjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:waveform-path-badge-plus" /></template>
