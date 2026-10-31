<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai5y9abrj.css';
import '../../css/t/t5wv3ubfi.css';
import '../../css/v/vlejwkz4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="ai5y9abrj"/><path class="t5wv3ubfi"/><path class="vlejwkz4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:mongolia" /></template>
