<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8-k94bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b8-k94bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:object-group-solid" /></template>
