<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krfo0kbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="krfo0kbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:whale-tail" /></template>
