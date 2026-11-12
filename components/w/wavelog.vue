<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy7hzx7ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dy7hzx7ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wavelog" /></template>
