<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrumxpa0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jrumxpa0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:spray" /></template>
