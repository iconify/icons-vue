<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_62dabzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="k_62dabzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:whistle" /></template>
