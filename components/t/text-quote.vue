<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7e-4kxuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="c7e-4kxuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:text-quote" /></template>
