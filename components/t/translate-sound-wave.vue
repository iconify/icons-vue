<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye0liacoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye0liacoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:translate-sound-wave" /></template>
