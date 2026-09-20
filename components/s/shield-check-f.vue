<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4m8eac9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-1.5};
const content = `<path class="d4m8eac9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:shield-check-f" /></template>
