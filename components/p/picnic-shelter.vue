<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlq4g9a-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jlq4g9a-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:picnic-shelter" /></template>
