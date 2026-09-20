<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_1tuyjpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j_1tuyjpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-down-above-999" /></template>
