<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2dm4v5hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2dm4v5hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:target-line" /></template>
