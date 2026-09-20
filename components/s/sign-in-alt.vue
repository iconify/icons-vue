<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3qy1r37f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i3qy1r37f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:sign-in-alt" /></template>
