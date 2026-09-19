<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae5jc82yp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ae5jc82yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-profile" /></template>
