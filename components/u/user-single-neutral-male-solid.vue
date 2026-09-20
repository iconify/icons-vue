<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn35t6oxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cn35t6oxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:user-single-neutral-male-solid" /></template>
