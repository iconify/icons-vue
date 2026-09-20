<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9xj9c1ac.css';
import '../../css/e/ec97ebbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r9xj9c1ac"/><path class="ec97ebbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notion-mail" /></template>
