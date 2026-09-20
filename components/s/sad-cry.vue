<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpozg-01u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lpozg-01u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sad-cry" /></template>
