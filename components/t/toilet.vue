<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4glezq6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s4glezq6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:toilet" /></template>
