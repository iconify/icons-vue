<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7l1neb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j7l1neb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:windpump" /></template>
