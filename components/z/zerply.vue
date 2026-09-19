<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypohyzbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="ypohyzbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:zerply" /></template>
