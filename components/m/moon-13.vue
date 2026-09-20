<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1g1yybko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="v1g1yybko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-13" /></template>
