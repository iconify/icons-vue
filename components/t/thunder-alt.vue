<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez8bopsco.css';
import '../../css/i/io2oo-spz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ez8bopsco"/><path class="io2oo-spz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:thunder-alt" /></template>
