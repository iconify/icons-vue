<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djmxe_n-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djmxe_n-i primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:outdent-duotone" /></template>
