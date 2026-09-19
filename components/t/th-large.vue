<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk7y3tbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="mk7y3tbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:th-large" /></template>
