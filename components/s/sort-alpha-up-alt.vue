<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us7pqh5os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="us7pqh5os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sort-alpha-up-alt" /></template>
