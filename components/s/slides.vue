<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oet9micqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oet9micqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:slides" /></template>
