<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm2q63wql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fm2q63wql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:traffic2-filled" /></template>
