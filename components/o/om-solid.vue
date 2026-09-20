<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1kek3bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j1kek3bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:om-solid" /></template>
