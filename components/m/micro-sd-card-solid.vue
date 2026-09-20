<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxw-ku7it.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="xxw-ku7it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:micro-sd-card-solid" /></template>
