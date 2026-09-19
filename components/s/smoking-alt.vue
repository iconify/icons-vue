<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5duaqbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1344};
const content = `<path class="b5duaqbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:smoking-alt" /></template>
