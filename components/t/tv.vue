<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag6ih3byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="ag6ih3byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:tv" /></template>
