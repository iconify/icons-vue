<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jss17mrbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jss17mrbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:two-button-mouse-small" /></template>
