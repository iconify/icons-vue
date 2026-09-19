<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uche6nifg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="uche6nifg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:user-filled" /></template>
