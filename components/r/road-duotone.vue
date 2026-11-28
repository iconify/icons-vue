<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs60qn8ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zs60qn8ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:road-duotone" /></template>
