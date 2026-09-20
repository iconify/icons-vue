<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2-ckur5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c2-ckur5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vending-machine-with-question-mark" /></template>
