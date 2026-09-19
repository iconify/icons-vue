<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwjw1vf0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="iwjw1vf0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:test-user-solid" /></template>
