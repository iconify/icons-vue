<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lob4abbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lob4abbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:surveymonkey-dark" /></template>
