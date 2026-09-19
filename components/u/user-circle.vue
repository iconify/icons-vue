<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/robw075fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="robw075fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-circle" /></template>
