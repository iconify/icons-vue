<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hceee5bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hceee5bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-add-2-line" /></template>
