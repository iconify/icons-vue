<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plh2b-bni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="plh2b-bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:task-list-edit-remix" /></template>
