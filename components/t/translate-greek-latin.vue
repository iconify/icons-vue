<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_7ttr2sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="b_7ttr2sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:translate-greek-latin" /></template>
