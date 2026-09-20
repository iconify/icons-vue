<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv1meoboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv1meoboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mastercard" /></template>
