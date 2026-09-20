<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7gxoccmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7gxoccmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-add-fill" /></template>
