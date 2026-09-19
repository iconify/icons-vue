<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu1h-6bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fu1h-6bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:scales" /></template>
