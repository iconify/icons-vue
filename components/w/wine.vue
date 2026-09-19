<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh2vkhb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oh2vkhb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:wine" /></template>
