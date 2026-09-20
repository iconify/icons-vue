<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8wfy4buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8wfy4buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-unknown-filled" /></template>
