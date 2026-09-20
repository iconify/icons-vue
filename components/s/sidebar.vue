<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdv0l904k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jdv0l904k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:sidebar" /></template>
