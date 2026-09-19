<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvk4zyyjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tvk4zyyjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:mail2" /></template>
