<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlivm3flo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="hlivm3flo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:tampermonkey" /></template>
