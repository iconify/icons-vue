<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4jmgynoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="j4jmgynoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-list-fill" /></template>
