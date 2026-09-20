<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3l944b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3l944b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:vaccine-bottle-off" /></template>
