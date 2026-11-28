<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkag413ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkag413ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:message-square-edit" /></template>
