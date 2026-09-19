<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0a3f7ftz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="e0a3f7ftz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-hiking" /></template>
