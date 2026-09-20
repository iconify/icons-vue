<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl8-cidno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl8-cidno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:razorpay" /></template>
