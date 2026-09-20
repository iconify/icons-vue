<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np6v3sb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="np6v3sb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tag-connection-view" /></template>
