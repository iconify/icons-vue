<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhpicrbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zhpicrbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-standing-aiming-archery-bow" /></template>
