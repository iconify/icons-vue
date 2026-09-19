<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1fqgkbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":960};
const content = `<path class="j1fqgkbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:outerborders" /></template>
