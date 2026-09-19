<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hiwy8cc9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hiwy8cc9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:skull" /></template>
