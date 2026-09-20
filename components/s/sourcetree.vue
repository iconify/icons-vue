<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c54dcrbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c54dcrbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sourcetree" /></template>
