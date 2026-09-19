<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-zstca3u.css';
import '../../css/q/qivzlzbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d-zstca3u"/><path class="qivzlzbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:skip-forward-solid-filled" /></template>
