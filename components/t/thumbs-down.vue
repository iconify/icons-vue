<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g88r1cckn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g88r1cckn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:thumbs-down" /></template>
