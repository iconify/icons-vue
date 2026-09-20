<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go8c5qwvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go8c5qwvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:rugby" /></template>
