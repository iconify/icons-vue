<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_nz6x7vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="b_nz6x7vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:waveform-path-ecg" /></template>
