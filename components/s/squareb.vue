<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7i7fkpni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="v7i7fkpni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squareb" /></template>
