<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1nphnbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v1nphnbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plus-minus-outline" /></template>
