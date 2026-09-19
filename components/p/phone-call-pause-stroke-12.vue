<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhe2hvncw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bhe2hvncw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-pause-stroke-12" /></template>
