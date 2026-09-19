<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9-op4kkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b9-op4kkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:shocked2" /></template>
