<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5en5pmvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":1025};
const content = `<path class="s5en5pmvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:medal" /></template>
