<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cep-q2bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cep-q2bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:printer-solid" /></template>
