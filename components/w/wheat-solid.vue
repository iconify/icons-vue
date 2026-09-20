<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j43404xrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j43404xrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:wheat-solid" /></template>
