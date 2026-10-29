<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tew7bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9tew7bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wrap-text-solid" /></template>
