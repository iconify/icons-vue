<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5hbqvx0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="o5hbqvx0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:plus" /></template>
