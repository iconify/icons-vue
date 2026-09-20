<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/a/a3y69p.css';
import '../../css/c/cquv0f.css';
import '../../css/s/so-from-26.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c a3y69p"/><path class="a0m25c cquv0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:navigation-right-up" /></template>
