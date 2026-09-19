<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byk0tmp-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":850};
const content = `<path class="byk0tmp-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:notification" /></template>
