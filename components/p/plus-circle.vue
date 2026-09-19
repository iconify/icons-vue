<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me4702b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me4702b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:plus-circle" /></template>
