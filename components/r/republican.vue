<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9yrrwb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="a9yrrwb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:republican" /></template>
