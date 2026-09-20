<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceonq4b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="ceonq4b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:status-alert" /></template>
