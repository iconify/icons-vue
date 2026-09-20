<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff5t4wldt.css';
import '../../css/w/ww30y30st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ff5t4wldt"/><path class="ww30y30st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pdfcraft" /></template>
