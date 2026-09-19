<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9slh7bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9slh7bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:paper-bag" /></template>
