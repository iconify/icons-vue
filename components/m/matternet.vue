<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyy6gn3df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hyy6gn3df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:matternet" /></template>
