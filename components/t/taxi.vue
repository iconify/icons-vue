<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2uby840p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t2uby840p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:taxi" /></template>
