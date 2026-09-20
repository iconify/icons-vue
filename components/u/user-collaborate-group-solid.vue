<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5h0hrbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d5h0hrbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-collaborate-group-solid" /></template>
