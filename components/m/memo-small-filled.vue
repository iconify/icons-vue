<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akb6c-68i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="akb6c-68i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:memo-small-filled" /></template>
