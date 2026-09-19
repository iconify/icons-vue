<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3rh6-bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p3rh6-bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:shower" /></template>
