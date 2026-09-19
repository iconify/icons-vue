<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcj8v3szg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="pcj8v3szg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:phonescreensize" /></template>
