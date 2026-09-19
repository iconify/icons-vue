<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhtg83bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mhtg83bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:socks" /></template>
