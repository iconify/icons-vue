<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oynu28bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oynu28bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:red-old" /></template>
