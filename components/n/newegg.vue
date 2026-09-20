<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp473r5qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp473r5qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:newegg" /></template>
