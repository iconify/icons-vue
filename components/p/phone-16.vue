<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwjk6jbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qwjk6jbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:phone-16" /></template>
