<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgmda8buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jgmda8buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:user-x-mark-20-solid" /></template>
