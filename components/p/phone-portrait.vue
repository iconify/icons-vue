<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e00fw2bit.css';
import '../../css/v/vz-n1gf_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><path id="SVGpHmZZbqf" class="e00fw2bit"/></defs><use href="#SVGpHmZZbqf"/><path class="vz-n1gf_b"/><use href="#SVGpHmZZbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:phone-portrait" /></template>
