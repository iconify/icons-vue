<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc2-ddicz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nc2-ddicz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:upload-2" /></template>
