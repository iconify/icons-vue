<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cty24_dra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cty24_dra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:text-size" /></template>
