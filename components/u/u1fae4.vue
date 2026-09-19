<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njcg00bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="njcg00bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:u1fae4" /></template>
