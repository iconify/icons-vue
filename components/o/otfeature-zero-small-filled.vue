<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sebvhx9qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sebvhx9qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-zero-small-filled" /></template>
