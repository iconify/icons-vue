<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df254mb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="df254mb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:play-one" /></template>
