<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt3e4cb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yt3e4cb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:mail" /></template>
