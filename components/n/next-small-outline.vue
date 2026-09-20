<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vadamjbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vadamjbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:next-small-outline" /></template>
