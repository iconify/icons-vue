<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyau3c7zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kyau3c7zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:phone-alt" /></template>
