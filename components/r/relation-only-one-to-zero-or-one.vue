<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5x9ex2ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5x9ex2ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-only-one-to-zero-or-one" /></template>
