<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi-lltbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="vi-lltbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-circle-check" /></template>
