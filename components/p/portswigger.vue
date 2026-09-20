<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja06olbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ja06olbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:portswigger" /></template>
