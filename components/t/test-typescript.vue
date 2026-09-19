<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lov-w_bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lov-w_bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:test-typescript" /></template>
