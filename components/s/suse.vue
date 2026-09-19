<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja584fb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ja584fb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:suse" /></template>
