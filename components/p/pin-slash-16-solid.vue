<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo1ge9bch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vo1ge9bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pin-slash-16-solid" /></template>
