<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7xdkkb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7xdkkb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:post-terms" /></template>
