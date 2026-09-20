<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-3wgobyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l-3wgobyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:usulnet-dark" /></template>
