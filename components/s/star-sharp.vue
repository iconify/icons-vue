<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3ppa3bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c3ppa3bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:star-sharp" /></template>
