<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olr6uaclq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="olr6uaclq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:photoshop" /></template>
