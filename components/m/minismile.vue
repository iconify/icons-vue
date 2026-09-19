<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7v6ehbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":896};
const content = `<path class="o7v6ehbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:minismile" /></template>
