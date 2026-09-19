<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbgflfbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nbgflfbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:three-button-mouse-alt" /></template>
