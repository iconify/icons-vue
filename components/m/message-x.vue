<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj4y8ib7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bj4y8ib7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-x" /></template>
