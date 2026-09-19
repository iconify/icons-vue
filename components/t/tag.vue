<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-7g6-bii.css';
import '../../css/a/a7xkecbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="b-7g6-bii"/><path class="a7xkecbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:tag" /></template>
