<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knvuo4bci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="knvuo4bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shed" /></template>
