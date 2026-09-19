<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmpycxb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":384};
const content = `<path class="wmpycxb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:sec-3" /></template>
