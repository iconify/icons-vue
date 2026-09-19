<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfq9if7sm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfq9if7sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:route" /></template>
