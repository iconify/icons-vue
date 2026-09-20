<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6ankybaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="z6ankybaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:post" /></template>
