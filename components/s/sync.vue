<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsrgtvbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="rsrgtvbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sync" /></template>
