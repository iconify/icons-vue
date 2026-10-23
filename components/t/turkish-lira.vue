<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-6b7e9ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-6b7e9ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:turkish-lira" /></template>
