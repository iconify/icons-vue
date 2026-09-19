<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c61345ufy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="c61345ufy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:memories-badge-minus" /></template>
