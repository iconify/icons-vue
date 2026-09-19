<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2wo1bdya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="j2wo1bdya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:shopping-bag-1" /></template>
