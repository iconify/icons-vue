<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df35pablj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="df35pablj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:send" /></template>
