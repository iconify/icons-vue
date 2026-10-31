<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6ol74bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6ol74bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shankh-gloss" /></template>
