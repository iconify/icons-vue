<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riqi-tbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="riqi-tbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:rdio" /></template>
