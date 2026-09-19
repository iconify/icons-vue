<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il4lh3bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="il4lh3bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:reply" /></template>
