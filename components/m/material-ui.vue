<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxr70vbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxr70vbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:material-ui" /></template>
