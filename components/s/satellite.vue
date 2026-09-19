<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcoia7b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="tcoia7b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:satellite" /></template>
