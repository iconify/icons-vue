<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi8_oub_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mi8_oub_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:user-warning" /></template>
