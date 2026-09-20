<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x10eg_btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x10eg_btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:u" /></template>
