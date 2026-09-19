<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezb6zpbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ezb6zpbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:svelte" /></template>
