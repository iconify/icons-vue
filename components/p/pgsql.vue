<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2cez91zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="u2cez91zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pgsql" /></template>
