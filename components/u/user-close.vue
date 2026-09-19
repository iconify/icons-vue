<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksddewbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksddewbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:user-close" /></template>
