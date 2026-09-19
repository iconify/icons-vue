<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4vs8xdmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":1024};
const content = `<path class="y4vs8xdmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:vial" /></template>
