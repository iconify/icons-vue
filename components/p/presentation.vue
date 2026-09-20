<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svz5apblp.css';
import '../../css/s/sk_7s2z0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="svz5apblp"/><path class="sk_7s2z0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:presentation" /></template>
