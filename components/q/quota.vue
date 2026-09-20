<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9q2-odkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k9q2-odkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:quota" /></template>
