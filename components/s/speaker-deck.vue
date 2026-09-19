<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq71x92eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jq71x92eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:speaker-deck" /></template>
