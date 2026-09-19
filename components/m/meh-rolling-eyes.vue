<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzta2cbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="kzta2cbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:meh-rolling-eyes" /></template>
