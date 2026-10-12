<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/naysjv-ce.css';
import '../../css/g/g-mtj-z5m.css';
import '../../css/i/iqtg16bzl.css';
import '../../css/s/skp8tjssj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="naysjv-ce"/><path class="g-mtj-z5m"/><path class="iqtg16bzl"/><path class="skp8tjssj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-star-duotone" /></template>
