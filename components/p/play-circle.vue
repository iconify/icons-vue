<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi8mhqxrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hi8mhqxrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:play-circle" /></template>
