<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezigzjbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ezigzjbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:papal-cross" /></template>
