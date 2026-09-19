<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4y0izbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="w4y0izbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:recordingtape" /></template>
