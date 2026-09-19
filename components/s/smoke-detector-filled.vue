<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3vu-5e0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3vu-5e0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:smoke-detector-filled" /></template>
