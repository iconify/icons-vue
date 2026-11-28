<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5a2oxabs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5a2oxabs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:rocket-solid" /></template>
