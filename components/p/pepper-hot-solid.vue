<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciuqjug0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ciuqjug0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:pepper-hot-solid" /></template>
