<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6jyqbc7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="j6jyqbc7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:plug" /></template>
