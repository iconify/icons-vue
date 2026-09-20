<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgkc1nqpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgkc1nqpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-bottom-close" /></template>
