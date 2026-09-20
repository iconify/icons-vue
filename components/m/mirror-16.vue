<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibtii7bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ibtii7bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:mirror-16" /></template>
