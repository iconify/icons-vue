<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0_qoqb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="n0_qoqb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:video" /></template>
