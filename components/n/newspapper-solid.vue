<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g92vniboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g92vniboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:newspapper-solid" /></template>
