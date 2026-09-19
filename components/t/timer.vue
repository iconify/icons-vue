<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm_8qdbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="dm_8qdbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:timer" /></template>
