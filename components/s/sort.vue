<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zskg0iypq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zskg0iypq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:sort" /></template>
