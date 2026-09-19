<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmf0blbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qmf0blbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:vmware" /></template>
