<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um0cmtqka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="um0cmtqka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:redmine-dark" /></template>
