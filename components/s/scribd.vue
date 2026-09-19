<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npypv3mzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="npypv3mzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:scribd" /></template>
