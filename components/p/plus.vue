<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgk4apf_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgk4apf_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:plus" /></template>
