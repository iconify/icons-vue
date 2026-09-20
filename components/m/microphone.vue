<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ary8e2ekk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ary8e2ekk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:microphone" /></template>
