<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv1b90jbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wv1b90jbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-on-ground-dragging-raft-to-water" /></template>
