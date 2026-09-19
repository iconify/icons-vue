<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlhlbkp3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zlhlbkp3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:yes-alt" /></template>
