<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3k4apb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u3k4apb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-riding-tube-on-water" /></template>
