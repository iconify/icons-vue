<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olsnwmrvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="olsnwmrvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:pen-fancy" /></template>
