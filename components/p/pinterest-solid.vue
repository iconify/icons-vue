<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miwen_ndd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miwen_ndd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:pinterest-solid" /></template>
