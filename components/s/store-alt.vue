<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie-qqtb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ie-qqtb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:store-alt" /></template>
