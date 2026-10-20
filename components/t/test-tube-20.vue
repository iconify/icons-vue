<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxwb8tbxv.css';
import '../../css/d/dsco5xu2d.css';
import '../../css/e/e2j9qob0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pxwb8tbxv"/><path class="dsco5xu2d"/><path class="e2j9qob0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:test-tube-20" /></template>
