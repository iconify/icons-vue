<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0ygf8bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0ygf8bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shield-flash-line" /></template>
