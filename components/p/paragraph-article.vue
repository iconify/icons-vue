<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm53bibrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm53bibrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:paragraph-article" /></template>
