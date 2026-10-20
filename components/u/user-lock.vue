<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8jr52b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8jr52b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-lock" /></template>
