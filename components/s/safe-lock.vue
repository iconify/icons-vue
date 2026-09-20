<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yovaf8ljk.css';
import '../../css/b/b_ado9bqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yovaf8ljk"/><path class="b_ado9bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:safe-lock" /></template>
