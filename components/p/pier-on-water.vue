<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui6pqfb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ui6pqfb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pier-on-water" /></template>
