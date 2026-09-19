<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au8nzfblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="au8nzfblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:trolleybus" /></template>
