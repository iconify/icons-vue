<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8gm18wil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="p8gm18wil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:previous" /></template>
