<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4n1yqnky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4n1yqnky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:question" /></template>
