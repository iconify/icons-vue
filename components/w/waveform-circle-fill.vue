<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw_pdhz4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fw_pdhz4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:waveform-circle-fill" /></template>
