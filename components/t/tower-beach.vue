<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd6im6kgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd6im6kgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tower-beach" /></template>
