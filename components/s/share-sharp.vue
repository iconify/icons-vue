<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2kwq3gxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2kwq3gxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:share-sharp" /></template>
