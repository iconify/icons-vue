<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyhewobvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dyhewobvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:medical-bag-solid" /></template>
