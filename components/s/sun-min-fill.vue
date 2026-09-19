<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp5o2yxoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gp5o2yxoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sun-min-fill" /></template>
