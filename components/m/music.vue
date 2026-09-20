<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq8qcye-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="gq8qcye-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:music" /></template>
