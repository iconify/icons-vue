<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvc0lacwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dvc0lacwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:photo-solid" /></template>
