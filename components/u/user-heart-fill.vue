<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z58k0jbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z58k0jbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-heart-fill" /></template>
