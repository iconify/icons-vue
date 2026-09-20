<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6e0npbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e6e0npbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-balancing" /></template>
