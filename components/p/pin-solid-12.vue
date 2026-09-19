<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot2q9jb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ot2q9jb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:pin-solid-12" /></template>
