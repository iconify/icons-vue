<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f66secynb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f66secynb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:plus-circle-outline" /></template>
