<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_s4tsbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a_s4tsbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:smile" /></template>
