<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7nzr5vfc.css';
import '../../css/w/wbrmur83b.css';
import '../../css/t/tlpzu3bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z7nzr5vfc"/><path class="wbrmur83b"/><path class="tlpzu3bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pickup-truck-20-bold" /></template>
