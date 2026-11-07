<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9o-8lbqq.css';
import '../../css/f/f9lebcb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9o-8lbqq"/><path clip-rule="evenodd" class="f9lebcb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:walking-bold" /></template>
