<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm6olf9fp.css';
import '../../css/h/hr6xjbb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="zm6olf9fp"/><path class="hr6xjbb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:play-video" /></template>
