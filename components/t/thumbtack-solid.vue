<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5n0-tron.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5n0-tron"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:thumbtack-solid" /></template>
