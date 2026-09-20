<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_qq53ffi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_qq53ffi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:uniqlo-ja" /></template>
