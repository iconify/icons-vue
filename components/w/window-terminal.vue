<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmi7qy-ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pmi7qy-ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:window-terminal" /></template>
