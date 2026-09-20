<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltf0sebud.css';
import '../../css/a/ahpr7q3lo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ltf0sebud"/><path class="ahpr7q3lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:pills" /></template>
