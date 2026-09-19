<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opjyjt5pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="opjyjt5pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:text-height" /></template>
