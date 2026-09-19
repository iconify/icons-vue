<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntrv586rn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ntrv586rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pigpens" /></template>
