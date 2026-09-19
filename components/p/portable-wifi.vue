<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t41rjyaqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":400};
const content = `<path class="t41rjyaqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:portable-wifi" /></template>
