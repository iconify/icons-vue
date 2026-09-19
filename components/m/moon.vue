<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyqk6kq5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyqk6kq5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:moon" /></template>
