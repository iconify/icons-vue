<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldh_0wm7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ldh_0wm7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:plus-square-on-square" /></template>
