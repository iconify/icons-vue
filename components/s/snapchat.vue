<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkrlu3b7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lkrlu3b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:snapchat" /></template>
