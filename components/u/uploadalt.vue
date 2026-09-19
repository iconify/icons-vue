<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-pezac1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a-pezac1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:uploadalt" /></template>
