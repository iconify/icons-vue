<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7853bbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7853bbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:meituan" /></template>
