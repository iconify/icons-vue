<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yupezqv6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yupezqv6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:material-for-mkdocs" /></template>
