<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4y-fjblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n4y-fjblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:thumbsup-16" /></template>
