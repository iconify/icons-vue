<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v71lst90i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v71lst90i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:map-pin-12" /></template>
