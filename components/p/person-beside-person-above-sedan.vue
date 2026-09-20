<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcb4e8b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bcb4e8b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-beside-person-above-sedan" /></template>
