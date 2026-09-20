<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivqi5kbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ivqi5kbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:notifications" /></template>
