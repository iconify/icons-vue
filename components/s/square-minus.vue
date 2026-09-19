<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdw2rotvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bdw2rotvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:square-minus" /></template>
