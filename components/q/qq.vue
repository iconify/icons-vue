<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mufh7bfhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mufh7bfhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:qq" /></template>
