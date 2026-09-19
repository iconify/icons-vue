<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyp08bp7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nyp08bp7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:play-forward-sharp" /></template>
