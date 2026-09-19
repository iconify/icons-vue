<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jve6oc-3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":717};
const content = `<path class="jve6oc-3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:walking" /></template>
