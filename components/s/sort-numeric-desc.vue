<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp-g37biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wp-g37biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:sort-numeric-desc" /></template>
