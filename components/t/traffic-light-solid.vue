<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcdtemq4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zcdtemq4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:traffic-light-solid" /></template>
