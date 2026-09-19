<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1t5l6sww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1t5l6sww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:newspapper-outline" /></template>
