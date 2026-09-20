<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9rq-8b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j9rq-8b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ups-dark" /></template>
