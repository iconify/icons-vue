<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6czdubni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1024};
const content = `<path class="q6czdubni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:notes" /></template>
