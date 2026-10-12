<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d_i5s9b1t.css';
import '../../css/s/skp8tjssj.css';
import '../../css/v/vu1o8o0qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d_i5s9b1t"/><path class="skp8tjssj"/><path class="vu1o8o0qr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-search-duotone" /></template>
