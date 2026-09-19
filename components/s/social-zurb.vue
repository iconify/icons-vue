<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abj0z4bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="abj0z4bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-zurb" /></template>
