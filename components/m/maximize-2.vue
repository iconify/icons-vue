<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkfjhxory.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkfjhxory"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:maximize-2" /></template>
