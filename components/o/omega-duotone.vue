<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmp7fsbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary tmp7fsbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:omega-duotone" /></template>
