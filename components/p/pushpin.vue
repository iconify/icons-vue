<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt3tjbgsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pt3tjbgsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:pushpin" /></template>
