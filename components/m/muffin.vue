<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oggrg6dkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oggrg6dkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:muffin" /></template>
