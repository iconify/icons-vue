<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw4uyb9sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fw4uyb9sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:mattermost" /></template>
