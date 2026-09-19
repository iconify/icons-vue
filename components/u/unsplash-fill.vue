<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhi-8zbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhi-8zbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:unsplash-fill" /></template>
