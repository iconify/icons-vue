<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6s1n5b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6s1n5b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:toilet-paper" /></template>
