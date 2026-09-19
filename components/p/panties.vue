<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el_f30bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="el_f30bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:panties" /></template>
