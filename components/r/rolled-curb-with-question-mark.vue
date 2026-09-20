<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqu27-g1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bqu27-g1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rolled-curb-with-question-mark" /></template>
