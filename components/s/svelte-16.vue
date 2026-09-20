<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1qercc3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c1qercc3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:svelte-16" /></template>
