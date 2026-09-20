<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elp_duv8g.css';
import '../../css/j/jl_m3bc1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="elp_duv8g"/><path class="jl_m3bc1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:sunset-filled" /></template>
