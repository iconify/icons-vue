<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq8ypobzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kq8ypobzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:user-remove" /></template>
