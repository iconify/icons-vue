<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu271i46h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"top":-2.5};
const content = `<path class="qu271i46h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:tags-f" /></template>
