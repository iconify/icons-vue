<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocb0xlwdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocb0xlwdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:phone-find-fill" /></template>
