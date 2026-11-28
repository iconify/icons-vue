<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/objv1ybmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="objv1ybmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-star-solid" /></template>
