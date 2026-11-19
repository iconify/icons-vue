<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucomdgbea.css';
import '../../css/m/m9uodidsu.css';
import '../../css/w/wx7rgmjkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="ucomdgbea"/><path class="m9uodidsu"/><circle class="wx7rgmjkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyxiontech-pdf-tools" /></template>
