<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b146bit4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b146bit4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:shield-1-solid" /></template>
