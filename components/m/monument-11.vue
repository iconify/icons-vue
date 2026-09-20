<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge-k3mw8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ge-k3mw8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:monument-11" /></template>
