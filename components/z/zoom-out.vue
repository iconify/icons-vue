<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc0nou-7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="uc0nou-7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:zoom-out" /></template>
