<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijqnryukn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijqnryukn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:red-hat-open-shift" /></template>
