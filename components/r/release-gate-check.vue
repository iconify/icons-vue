<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t37m8-r3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="t37m8-r3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:release-gate-check" /></template>
