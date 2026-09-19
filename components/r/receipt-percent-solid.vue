<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzv3d8bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bzv3d8bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:receipt-percent-solid" /></template>
