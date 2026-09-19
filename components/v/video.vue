<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sukewzbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":614};
const content = `<path class="sukewzbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:video" /></template>
