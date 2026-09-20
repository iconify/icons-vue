<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg24q37mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jg24q37mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-holding-barbell" /></template>
