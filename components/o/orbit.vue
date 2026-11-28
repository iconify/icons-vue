<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5fi47jmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5fi47jmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:orbit" /></template>
