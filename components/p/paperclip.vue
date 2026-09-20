<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvzfzdppk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pvzfzdppk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:paperclip" /></template>
