<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/s/ssaqwk.css';
import '../../css/n/na274t.css';
import '../../css/j/jip9fo.css';
import '../../css/p/p91oqf.css';
import '../../css/s/so-from-16.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c ssaqwk"/><path class="a0m25c na274t"/><path class="a0m25c jip9fo"/><path class="a0m25c p91oqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:menu-fold-right" /></template>
