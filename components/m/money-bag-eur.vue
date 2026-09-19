<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihf1r4aus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ihf1r4aus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:money-bag-eur" /></template>
