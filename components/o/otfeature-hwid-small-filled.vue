<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8osg5fzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="j8osg5fzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-hwid-small-filled" /></template>
