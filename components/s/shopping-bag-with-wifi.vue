<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bckfujq4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bckfujq4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-wifi" /></template>
