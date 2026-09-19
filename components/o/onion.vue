<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbn2bd74u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fbn2bd74u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:onion" /></template>
