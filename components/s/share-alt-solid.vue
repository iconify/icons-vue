<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsu3e4aql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qsu3e4aql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:share-alt-solid" /></template>
