<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usv_bxr6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usv_bxr6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tistory" /></template>
