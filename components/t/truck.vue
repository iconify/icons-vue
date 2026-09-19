<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o705soh5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o705soh5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:truck" /></template>
