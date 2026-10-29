<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyxnp4cfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyxnp4cfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:thandai-solid" /></template>
