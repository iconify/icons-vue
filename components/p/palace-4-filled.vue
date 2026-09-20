<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm9y4iblw.css';
import '../../css/z/zkrbon-zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm9y4iblw"/><path class="zkrbon-zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:palace-4-filled" /></template>
