<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi65es6xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi65es6xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:maximize" /></template>
