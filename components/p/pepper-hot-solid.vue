<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw7yodbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zw7yodbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:pepper-hot-solid" /></template>
