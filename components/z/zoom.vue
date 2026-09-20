<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6eow0bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6eow0bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:zoom" /></template>
