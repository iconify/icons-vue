<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4volpbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4volpbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:outdent-solid" /></template>
