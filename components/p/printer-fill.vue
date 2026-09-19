<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4fiq7b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4fiq7b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:printer-fill" /></template>
