<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gayi84bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gayi84bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-riding-bicycle-on-crosswalk" /></template>
