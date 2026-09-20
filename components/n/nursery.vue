<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huszaob7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="huszaob7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:nursery" /></template>
