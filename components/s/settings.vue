<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4_czfbpz.css';
import '../../css/u/uhn9qnbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r4_czfbpz"/><path class="uhn9qnbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:settings" /></template>
