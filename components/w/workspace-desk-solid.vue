<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7273vwtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="c7273vwtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:workspace-desk-solid" /></template>
