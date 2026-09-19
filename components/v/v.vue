<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usjw9sgjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="usjw9sgjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:v" /></template>
