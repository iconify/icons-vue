<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1xh9tbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="s1xh9tbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:maximize-1-remix" /></template>
