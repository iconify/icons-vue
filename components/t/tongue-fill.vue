<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owpd0cb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owpd0cb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tongue-fill" /></template>
