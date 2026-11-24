<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhugqhbem.css';
import '../../css/c/ct2edwbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhugqhbem"/><path class="ct2edwbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sticky-note-off-filled" /></template>
