<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjl_jbb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-5};
const content = `<path class="rjl_jbb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:signal" /></template>
