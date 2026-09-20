<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6fabdwkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g6fabdwkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:star-small-outline" /></template>
