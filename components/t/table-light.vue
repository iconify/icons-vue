<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icemalpcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icemalpcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:table-light" /></template>
