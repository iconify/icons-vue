<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b46jbeb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b46jbeb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:signage-3-solid" /></template>
