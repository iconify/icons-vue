<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3gqwcb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="r3gqwcb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:paragraph" /></template>
