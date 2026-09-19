<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0tmkpb-w.css';
import '../../css/f/f_i5tj91f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<rect class="g0tmkpb-w"/><path class="f_i5tj91f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:mobile-phone-fill-12" /></template>
