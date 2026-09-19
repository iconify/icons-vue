<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta53jqbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ta53jqbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:school-check-alt-outline" /></template>
