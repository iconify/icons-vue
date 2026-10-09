<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i48le1b7u.css';
import '../../css/w/wx0wzhb6i.css';
import '../../css/a/amp8719fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i48le1b7u"/><path class="wx0wzhb6i"/><path class="amp8719fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:table-20-bold" /></template>
