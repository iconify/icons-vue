<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9kn9pbtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="t9kn9pbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:share-alt-filled" /></template>
