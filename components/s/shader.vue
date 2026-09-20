<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-idt_63d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-idt_63d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:shader" /></template>
