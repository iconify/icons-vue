<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjtn75b-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="kjtn75b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:newspaper" /></template>
