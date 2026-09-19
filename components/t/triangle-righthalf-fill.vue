<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlbqyv7xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jlbqyv7xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:triangle-righthalf-fill" /></template>
