<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iybzt3kih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="iybzt3kih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:share-from-square" /></template>
