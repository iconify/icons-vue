<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqzifl2_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cqzifl2_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:right-then-curving-down-arrow-small" /></template>
