<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6av6r76k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g6av6r76k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:xamarin-logo" /></template>
