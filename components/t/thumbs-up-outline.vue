<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oflno8b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oflno8b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:thumbs-up-outline" /></template>
