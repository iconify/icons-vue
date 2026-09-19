<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g30nbhb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g30nbhb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:navigation-2-outline" /></template>
