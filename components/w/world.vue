<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvvot-35f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":850};
const content = `<path class="gvvot-35f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:world" /></template>
