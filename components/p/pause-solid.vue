<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy9631bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zy9631bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:pause-solid" /></template>
