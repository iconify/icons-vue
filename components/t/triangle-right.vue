<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtd9lvb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jtd9lvb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:triangle-right" /></template>
