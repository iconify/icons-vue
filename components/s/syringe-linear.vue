<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tejvvmbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tejvvmbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:syringe-linear" /></template>
