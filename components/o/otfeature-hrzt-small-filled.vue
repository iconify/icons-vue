<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4v-gabjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="o4v-gabjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-hrzt-small-filled" /></template>
