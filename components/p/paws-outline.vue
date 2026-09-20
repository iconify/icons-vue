<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_c0vp4vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q_c0vp4vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:paws-outline" /></template>
