<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwkkdgb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wwkkdgb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:password-pencil-16-solid" /></template>
