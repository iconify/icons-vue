<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnmjoyxcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnmjoyxcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:nurse-filled" /></template>
