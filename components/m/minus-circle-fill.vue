<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxn9sbcuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jxn9sbcuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:minus-circle-fill" /></template>
