<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imie70-7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imie70-7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:rewind" /></template>
