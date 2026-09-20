<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm-p47dmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dm-p47dmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:setting-o" /></template>
