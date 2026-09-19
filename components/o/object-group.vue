<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esv2aeb_b.css';
import '../../css/g/g0ixy-bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="esv2aeb_b"/><path class="g0ixy-bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:object-group" /></template>
