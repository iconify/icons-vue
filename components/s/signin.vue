<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og-t-ob6a.css';
import '../../css/z/zvp4gxblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og-t-ob6a"/><path class="zvp4gxblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:signin" /></template>
