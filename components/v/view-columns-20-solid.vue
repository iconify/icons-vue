<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muu80cxvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="muu80cxvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:view-columns-20-solid" /></template>
