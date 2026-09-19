<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfqd3kbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vfqd3kbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:scale-balanced-solid" /></template>
