<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh93kyo3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh93kyo3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:world-scout" /></template>
