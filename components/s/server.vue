<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp84ttcgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wp84ttcgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:server" /></template>
