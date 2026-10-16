<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b611vubcy.css';
import '../../css/f/fg-wh3qoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b611vubcy"/><path class="fg-wh3qoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:seabed-survey-48-bold" /></template>
