<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymdz2acqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymdz2acqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:ticket-solid" /></template>
