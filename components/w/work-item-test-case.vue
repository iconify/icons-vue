<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blwwl03cq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="blwwl03cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:work-item-test-case" /></template>
