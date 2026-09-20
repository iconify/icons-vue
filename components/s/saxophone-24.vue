<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/updm7mb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="updm7mb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:saxophone-24" /></template>
