<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di7af1s5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="di7af1s5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:money-outline" /></template>
