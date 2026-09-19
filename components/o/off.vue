<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq-5i-b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nq-5i-b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:off" /></template>
