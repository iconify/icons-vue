<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llnp5hb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="llnp5hb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:z" /></template>
