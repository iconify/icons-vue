<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umplx46gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umplx46gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:notebook" /></template>
