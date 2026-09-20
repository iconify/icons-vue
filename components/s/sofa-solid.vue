<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f33b351rw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f33b351rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:sofa-solid" /></template>
