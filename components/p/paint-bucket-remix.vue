<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv72_cb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jv72_cb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:paint-bucket-remix" /></template>
