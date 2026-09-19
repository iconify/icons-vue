<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hixq24oop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":646};
const content = `<path class="hixq24oop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:table" /></template>
