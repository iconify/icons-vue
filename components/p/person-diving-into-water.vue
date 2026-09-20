<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz4bzpbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yz4bzpbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-diving-into-water" /></template>
