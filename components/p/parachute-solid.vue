<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk_v_3bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dk_v_3bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:parachute-solid" /></template>
