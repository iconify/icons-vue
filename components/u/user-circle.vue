<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9y-47bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="q9y-47bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:user-circle" /></template>
