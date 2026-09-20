<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1v-cmfeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i1v-cmfeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:paste-16" /></template>
