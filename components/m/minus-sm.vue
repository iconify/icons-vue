<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjqk605uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjqk605uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:minus-sm" /></template>
