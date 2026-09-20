<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe9ard3ii.css';
import '../../css/o/o2ezd7b3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe9ard3ii"/><path class="o2ezd7b3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:sign-in-alt" /></template>
