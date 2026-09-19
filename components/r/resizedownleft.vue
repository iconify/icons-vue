<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6ewuabne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d6ewuabne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:resizedownleft" /></template>
