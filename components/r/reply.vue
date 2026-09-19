<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6d8yoboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6d8yoboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:reply" /></template>
