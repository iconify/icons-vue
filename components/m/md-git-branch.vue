<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcvd2fbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mcvd2fbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-git-branch" /></template>
