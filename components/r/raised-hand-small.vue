<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr0qihbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sr0qihbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:raised-hand-small" /></template>
