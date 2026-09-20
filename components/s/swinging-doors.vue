<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6uuk4btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q6uuk4btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:swinging-doors" /></template>
