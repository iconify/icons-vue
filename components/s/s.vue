<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9q2ikbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="v9q2ikbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:s" /></template>
