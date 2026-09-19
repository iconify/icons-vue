<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvxigfbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvxigfbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:skirt" /></template>
