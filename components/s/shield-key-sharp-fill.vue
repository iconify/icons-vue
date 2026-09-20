<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvhxqgbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pvhxqgbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-key-sharp-fill" /></template>
