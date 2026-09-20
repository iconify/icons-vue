<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-8u-ebvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-8u-ebvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:opslevel" /></template>
