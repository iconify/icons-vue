<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9xhsfe6o.css';
import '../../css/h/h35hfnqor.css';
import '../../css/e/ehfvjlbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":60,"height":60};
const content = `<path class="a9xhsfe6o"/><path class="h35hfnqor"/><path class="ehfvjlbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mobilizon" /></template>
