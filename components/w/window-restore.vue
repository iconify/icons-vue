<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8l-_n20z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z8l-_n20z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:window-restore" /></template>
