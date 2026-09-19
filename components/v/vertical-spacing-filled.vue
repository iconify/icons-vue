<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr2ppd9zo.css';
import '../../css/g/goxr0e-pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr2ppd9zo"/><rect class="goxr0e-pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vertical-spacing-filled" /></template>
