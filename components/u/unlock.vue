<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a96pf-b5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a96pf-b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:unlock" /></template>
