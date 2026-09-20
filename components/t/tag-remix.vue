<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vakb-pqpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vakb-pqpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:tag-remix" /></template>
