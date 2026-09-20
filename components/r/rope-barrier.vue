<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emvy9ge9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="emvy9ge9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:rope-barrier" /></template>
