<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmamuaclh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-9};
const content = `<path class="bmamuaclh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:more-horizontal-f" /></template>
