<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b85wjpb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b85wjpb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-arrow-dropdown-circle" /></template>
