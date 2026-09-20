<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-02oj49z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q-02oj49z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tag-with-dollar" /></template>
