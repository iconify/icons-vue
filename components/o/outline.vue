<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg-zg-b5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg-zg-b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:outline" /></template>
