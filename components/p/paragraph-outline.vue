<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk-zs26ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk-zs26ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:paragraph-outline" /></template>
