<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7jtysb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="c7jtysb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:note" /></template>
