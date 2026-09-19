<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gziqccc8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gziqccc8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:school-outline" /></template>
