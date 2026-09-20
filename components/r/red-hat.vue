<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0x3uhbzd.css';
import '../../css/l/lo8henb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g0x3uhbzd"/><path class="lo8henb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:red-hat" /></template>
