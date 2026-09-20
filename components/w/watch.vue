<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-qy24b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-qy24b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:watch" /></template>
