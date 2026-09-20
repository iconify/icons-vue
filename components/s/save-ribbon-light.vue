<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utw4vn0zz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utw4vn0zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:save-ribbon-light" /></template>
