<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxk486bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zxk486bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:translation-outdated-stroke-16" /></template>
