<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvavf9b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="bvavf9b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:zodiactaurus" /></template>
