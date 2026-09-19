<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id5-7hbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="id5-7hbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:s" /></template>
