<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi3t3pbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bi3t3pbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:test-suite" /></template>
