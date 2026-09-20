<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5ty9xb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o5ty9xb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:rocket-16" /></template>
