<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugbd4q--r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ugbd4q--r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pattern" /></template>
