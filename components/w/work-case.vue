<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrq4ddb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":496};
const content = `<path class="vrq4ddb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:work-case" /></template>
