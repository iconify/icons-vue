<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw2jjgk-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jw2jjgk-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-checked-1-filled" /></template>
