<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6c8adixg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f6c8adixg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:pharmacy-15" /></template>
