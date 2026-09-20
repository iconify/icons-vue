<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8lxn4b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8lxn4b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:strikethrough" /></template>
