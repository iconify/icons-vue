<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmkec5bnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bmkec5bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:nebraska" /></template>
