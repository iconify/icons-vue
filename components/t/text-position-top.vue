<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uttz4dh8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uttz4dh8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-position-top" /></template>
