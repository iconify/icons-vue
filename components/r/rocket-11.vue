<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asp71d7jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="asp71d7jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:rocket-11" /></template>
