<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8hfqvbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8hfqvbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:preference-vertical" /></template>
