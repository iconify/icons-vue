<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opcf11c4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opcf11c4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:wrench" /></template>
