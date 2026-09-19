<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4gp4vbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="s4gp4vbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:white-medium-star-small-filled" /></template>
