<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9bdq5bkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l9bdq5bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:unlock-alt-solid" /></template>
