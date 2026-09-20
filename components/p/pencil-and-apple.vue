<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm2ivuwhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vm2ivuwhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pencil-and-apple" /></template>
