<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk2zuomar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk2zuomar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:next" /></template>
