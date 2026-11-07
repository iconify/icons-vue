<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb5440rgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rb5440rgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:suspension-bolt-outline" /></template>
