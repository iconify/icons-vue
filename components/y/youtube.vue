<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecxavkbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":840,"height":790};
const content = `<path class="ecxavkbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:youtube" /></template>
