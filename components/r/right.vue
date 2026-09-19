<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aveyovb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":7,"height":16};
const content = `<path class="aveyovb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:right" /></template>
