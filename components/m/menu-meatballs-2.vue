<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtpdo_-qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="qtpdo_-qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:menu-meatballs-2" /></template>
