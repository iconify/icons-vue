<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtitqhbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="rtitqhbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:object-group" /></template>
