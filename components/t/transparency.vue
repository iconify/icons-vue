<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0fap9byy.css';
import '../../css/e/eax3dpvsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0fap9byy"/><path class="eax3dpvsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:transparency" /></template>
