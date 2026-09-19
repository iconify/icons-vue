<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2k03x09g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="h2k03x09g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:secret-han-circled" /></template>
