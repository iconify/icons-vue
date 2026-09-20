<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvjp70blq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hvjp70blq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-bars-no-signal" /></template>
