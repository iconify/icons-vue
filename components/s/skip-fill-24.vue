<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7odhzqfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7odhzqfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:skip-fill-24" /></template>
